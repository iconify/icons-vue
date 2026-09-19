<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s43y9hb-k.css';
import '../../css/w/wqz8cobop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s43y9hb-k"/><path class="wqz8cobop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-detail" /></template>
