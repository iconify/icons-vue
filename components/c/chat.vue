<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0vh8rd7c.css';
import '../../css/g/go-hdki3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0vh8rd7c"/><path class="go-hdki3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:chat" /></template>
