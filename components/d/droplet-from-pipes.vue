<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egrpiub7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="egrpiub7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:droplet-from-pipes" /></template>
