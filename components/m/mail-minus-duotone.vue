<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hmvf9hbln.css';
import '../../css/s/sigei6ulc.css';
import '../../css/x/xui3uacmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hmvf9hbln"/><path class="sigei6ulc"/><path class="xui3uacmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-minus-duotone" /></template>
