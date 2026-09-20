<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae22v_bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae22v_bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-next-outline" /></template>
