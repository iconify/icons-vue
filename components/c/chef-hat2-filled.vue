<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpw5ybclo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xpw5ybclo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chef-hat2-filled" /></template>
