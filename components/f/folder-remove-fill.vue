<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aly8xt7ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aly8xt7ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:folder-remove-fill" /></template>
