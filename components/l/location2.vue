<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwz76--ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gwz76--ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:location2" /></template>
