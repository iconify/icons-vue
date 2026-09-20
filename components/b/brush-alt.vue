<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn5db_b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kn5db_b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:brush-alt" /></template>
