<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c83uesblw.css';
import '../../css/e/eyx20b7zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c83uesblw"/><path class="eyx20b7zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:document-update-filled" /></template>
