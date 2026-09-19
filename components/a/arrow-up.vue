<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3nouv9br.css';
import '../../css/j/jcpgslicg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3nouv9br"/><path class="jcpgslicg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:arrow-up" /></template>
