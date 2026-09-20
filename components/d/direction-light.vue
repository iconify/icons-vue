<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/q/qa60wpbeh.css';
import '../../css/a/aescj0b_y.css';
import '../../css/z/zuii_hsfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="qa60wpbeh"/><path class="aescj0b_y"/><path class="zuii_hsfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:direction-light" /></template>
