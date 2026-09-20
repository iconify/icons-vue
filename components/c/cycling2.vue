<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpib5khjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hpib5khjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cycling2" /></template>
