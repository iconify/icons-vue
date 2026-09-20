<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk7w0m4zb.css';
import '../../css/d/dfm4qxg6q.css';
import '../../css/a/amyi9lblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk7w0m4zb"/><path class="dfm4qxg6q"/><path clip-rule="evenodd" class="amyi9lblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:idv" /></template>
