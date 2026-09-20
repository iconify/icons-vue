<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snp287xku.css';
import '../../css/l/lw_xbhbhf.css';
import '../../css/q/qo36bx88l.css';
import '../../css/x/xye16jy8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="snp287xku"/><path class="lw_xbhbhf"/><path class="qo36bx88l"/><path class="xye16jy8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:heart-suit" /></template>
