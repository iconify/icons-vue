<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy4if_byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="cy4if_byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:golang" /></template>
