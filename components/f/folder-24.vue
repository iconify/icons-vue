<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cec7lzbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cec7lzbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:folder-24" /></template>
