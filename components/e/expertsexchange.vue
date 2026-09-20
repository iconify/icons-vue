<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_yzqlbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_yzqlbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:expertsexchange" /></template>
