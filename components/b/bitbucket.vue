<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of9xrlbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1440,"height":1664};
const content = `<path class="of9xrlbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bitbucket" /></template>
