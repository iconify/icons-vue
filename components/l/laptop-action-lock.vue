<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/no-cdxbss.css';
import '../../css/b/blqx9nbej.css';
import '../../css/e/ewa20qhlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="no-cdxbss"/><path class="blqx9nbej"/><path class="ewa20qhlh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:laptop-action-lock" /></template>
