<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uayh04bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="uayh04bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:light-bulb" /></template>
