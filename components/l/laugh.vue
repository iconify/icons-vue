<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utqzt6bcp.css';
import '../../css/g/g1pjbqb5c.css';
import '../../css/q/qrntc0b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utqzt6bcp wm-k"/><path class="g1pjbqb5c wm-a"/><path class="qrntc0b5o wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:laugh" /></template>
