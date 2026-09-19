<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlp5gb8zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="tlp5gb8zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:baloon" /></template>
