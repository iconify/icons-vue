<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv_918bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lv_918bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:leg-with-varicose-veins" /></template>
