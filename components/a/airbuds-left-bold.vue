<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzw6lvbdu.css';
import '../../css/s/s1ws97bqa.css';
import '../../css/j/jtnd67jrf.css';
import '../../css/t/tn0g6-4-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dzw6lvbdu"/><path class="s1ws97bqa"/><path clip-rule="evenodd" class="jtnd67jrf"/><path clip-rule="evenodd" class="tn0g6-4-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-left-bold" /></template>
