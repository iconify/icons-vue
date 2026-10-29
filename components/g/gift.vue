<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqb102bra.css';
import '../../css/f/fcae2s9ga.css';
import '../../css/h/hw2roquec.css';
import '../../css/m/mch358e_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a wqb102bra"/><path class="fcae2s9ga wm-k"/><path class="hw2roquec wm-k"/><path class="mch358e_u wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:gift" /></template>
