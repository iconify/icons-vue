<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/g/g5tmdofwo.css';
import '../../css/c/cqd7zk_db.css';
import '../../css/b/byumf6bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="g5tmdofwo wm-shadow"/><path class="cqd7zk_db wm-shadow"/><path class="byumf6bwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:link" /></template>
