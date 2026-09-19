<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aps6ewwol.css';
import '../../css/d/dno86xatc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aps6ewwol"/><path class="dno86xatc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:eye-big" /></template>
