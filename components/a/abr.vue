<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t38kseb5u.css';
import '../../css/a/ahikl4b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t38kseb5u"/><path class="ahikl4b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:abr" /></template>
