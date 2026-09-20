<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmme1dbbu.css';
import '../../css/z/zju01gbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmme1dbbu"/><path class="zju01gbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:last-updates-light" /></template>
