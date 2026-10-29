<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/x/xr6pgbpqd.css';
import '../../css/g/g6kz9cc-f.css';
import '../../css/o/oj-txtbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="xr6pgbpqd"/><path class="g6kz9cc-f"/><path class="oj-txtbpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:cactus" /></template>
