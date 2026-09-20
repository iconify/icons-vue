<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byz9vkb6r.css';
import '../../css/k/ksdy6lv1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="byz9vkb6r"/><path class="ksdy6lv1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:lock-open-outline" /></template>
