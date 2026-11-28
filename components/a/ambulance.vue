<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g_7belbxz.css';
import '../../css/a/acjxr3b9a.css';
import '../../css/c/cfqx7ubxb.css';
import '../../css/m/m48o-0b4t.css';
import '../../css/x/xdanm-bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="g_7belbxz"/><path class="acjxr3b9a"/><path class="cfqx7ubxb"/><circle class="m48o-0b4t"/><circle class="xdanm-bki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ambulance" /></template>
