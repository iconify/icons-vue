<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5lssuuqi.css';
import '../../css/l/l6-eqnrfk.css';
import '../../css/l/lvzdmsb9x.css';
import '../../css/c/cf9gd76rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m5lssuuqi"/><circle class="l6-eqnrfk"/><path class="lvzdmsb9x"/><path class="cf9gd76rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudreve-light" /></template>
