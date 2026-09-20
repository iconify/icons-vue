<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5_s4_b4r.css';
import '../../css/i/iukkl9xoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5_s4_b4r"/><path class="iukkl9xoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:10set" /></template>
