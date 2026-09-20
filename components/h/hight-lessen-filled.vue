<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcq0wqbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kcq0wqbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:hight-lessen-filled" /></template>
