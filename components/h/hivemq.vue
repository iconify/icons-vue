<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl93aw29w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl93aw29w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hivemq" /></template>
