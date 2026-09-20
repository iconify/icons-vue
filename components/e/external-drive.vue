<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2id_fb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2id_fb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:external-drive" /></template>
