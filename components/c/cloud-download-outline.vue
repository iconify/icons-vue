<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tahbz4kss.css';
import '../../css/n/n6c26r64u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tahbz4kss"/><path clip-rule="evenodd" class="n6c26r64u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:cloud-download-outline" /></template>
