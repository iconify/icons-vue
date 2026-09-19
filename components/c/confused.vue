<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gshe_di8n.css';
import '../../css/w/ww076bcwj.css';
import '../../css/n/ngo67db0o.css';
import '../../css/d/dy-ttul4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gshe_di8n"/><path class="ww076bcwj"/><path class="ngo67db0o"/><path class="dy-ttul4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:confused" /></template>
