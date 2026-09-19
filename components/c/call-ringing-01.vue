<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztx86cb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztx86cb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-ringing-01" /></template>
