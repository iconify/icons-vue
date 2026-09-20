<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w0mp90b1v.css';
import '../../css/s/sv05mfuxd.css';
import '../../css/d/d_ldgic0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="w0mp90b1v"/><path class="sv05mfuxd"/><path class="d_ldgic0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:keyboard-delete-button" /></template>
