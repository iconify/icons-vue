<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acmwlabsp.css';
import '../../css/h/hzlua-bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="acmwlabsp"/><path class="hzlua-bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:email-mail-chat" /></template>
