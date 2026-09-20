<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttywsib-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ttywsib-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:align-txt-right-filled" /></template>
