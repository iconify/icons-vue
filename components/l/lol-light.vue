<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m7pevhgad.css';
import '../../css/d/dgll2bd_b.css';
import '../../css/q/q9cootb2b.css';
import '../../css/r/rwwgm7bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="m7pevhgad"/><circle class="dgll2bd_b"/><circle class="q9cootb2b"/><path clip-rule="evenodd" class="rwwgm7bpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:lol-light" /></template>
