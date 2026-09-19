<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_3qcrb_p.css';
import '../../css/k/kb-ng1w_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n_3qcrb_p"/><path clip-rule="evenodd" class="kb-ng1w_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:jinritoutiao" /></template>
