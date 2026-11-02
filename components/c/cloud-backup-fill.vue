<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbjfk5bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbjfk5bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-backup-fill" /></template>
