<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzy__5huq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzy__5huq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:htm" /></template>
