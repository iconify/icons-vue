<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm0xcdcgi.css';
import '../../css/b/b2xtvx_in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mm0xcdcgi"/><path class="b2xtvx_in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biochar-20-bold" /></template>
