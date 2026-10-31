<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/szmgnhb6c.css';
import '../../css/g/gx35_lbkf.css';
import '../../css/f/f7euivb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="szmgnhb6c"/><path class="gx35_lbkf"/><path class="f7euivb7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-a-duotone" /></template>
