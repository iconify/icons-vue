<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a59jnubsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a59jnubsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:information-solid" /></template>
