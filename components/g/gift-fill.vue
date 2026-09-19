<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acv3zackm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="acv3zackm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:gift-fill" /></template>
