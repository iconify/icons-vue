<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi609bcuk.css';
import '../../css/s/s-xq_4b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi609bcuk"/><path class="s-xq_4b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:aergo" /></template>
