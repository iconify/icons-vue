<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/g74vzqvdz.css';
import '../../css/v/vselo_bxr.css';
import '../../css/a/ang81xbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="g74vzqvdz"/><path class="vselo_bxr"/><path class="ang81xbkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:desktop-action-monitor-edit" /></template>
