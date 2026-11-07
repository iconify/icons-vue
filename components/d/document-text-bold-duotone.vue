<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4w_uybke.css';
import '../../css/g/gqzhmwbnh.css';
import '../../css/n/nrm_facaf.css';
import '../../css/j/jhtqjy4tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4w_uybke"/><path class="gqzhmwbnh"/><path class="nrm_facaf"/><path class="jhtqjy4tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:document-text-bold-duotone" /></template>
