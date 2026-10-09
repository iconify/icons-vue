<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8ikizbpd.css';
import '../../css/q/q_u57ubre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k8ikizbpd"/><path class="q_u57ubre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heading-20" /></template>
