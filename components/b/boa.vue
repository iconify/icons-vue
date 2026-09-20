<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv9bc4j-a.css';
import '../../css/z/zmmw0rbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kv9bc4j-a"/><path class="zmmw0rbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:boa" /></template>
