<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rbft5vf0c.css';
import '../../css/s/s2k0i-b_b.css';
import '../../css/f/f4oz41rqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rbft5vf0c"/><path class="s2k0i-b_b"/><path class="f4oz41rqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:graduation-cap-duotone" /></template>
