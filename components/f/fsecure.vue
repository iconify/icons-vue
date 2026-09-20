<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfd79i_uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfd79i_uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fsecure" /></template>
