<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qagxdnhak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qagxdnhak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:facebook-messenger-solid" /></template>
