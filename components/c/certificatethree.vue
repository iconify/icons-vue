<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cny_l1kll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="cny_l1kll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:certificatethree" /></template>
