<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzdi1u2bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bzdi1u2bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrows-left-right-above-waters" /></template>
