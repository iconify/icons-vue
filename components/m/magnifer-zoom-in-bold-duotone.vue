<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aygw_60rm.css';
import '../../css/r/r9znqobzq.css';
import '../../css/c/czuk_uaey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aygw_60rm"/><path clip-rule="evenodd" class="r9znqobzq"/><path class="czuk_uaey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifer-zoom-in-bold-duotone" /></template>
