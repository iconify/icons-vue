<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xye7cnqaq.css';
import '../../css/j/j06c4gncv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xye7cnqaq"/><path class="j06c4gncv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:arc" /></template>
