<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9fuv28jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g9fuv28jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:function-random-16" /></template>
