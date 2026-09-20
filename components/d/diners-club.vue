<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0wbvxbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0wbvxbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:diners-club" /></template>
