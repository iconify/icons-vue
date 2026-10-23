<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vpi-q2bht.css';
import '../../css/b/bk0dwpbms.css';
import '../../css/u/ue-rx-bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vpi-q2bht"/><path class="bk0dwpbms"/><path class="ue-rx-bbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-user-duotone" /></template>
