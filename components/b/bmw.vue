<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbsi7kbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bbsi7kbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:bmw" /></template>
