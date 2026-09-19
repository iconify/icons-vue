<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/higv-zb3q.css';
import '../../css/n/n1xy6nh9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="higv-zb3q"/><circle class="n1xy6nh9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:compass" /></template>
