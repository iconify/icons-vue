<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4og5_bir.css';
import '../../css/y/yypjo3b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a4og5_bir"/><path class="yypjo3b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:download-fill" /></template>
