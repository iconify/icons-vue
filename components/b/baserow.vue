<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4nwh4frs.css';
import '../../css/r/rkzev_bgd.css';
import '../../css/e/eywngtify.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f4nwh4frs"/><path class="rkzev_bgd"/><path class="eywngtify"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:baserow" /></template>
