<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5d2dxbxx.css';
import '../../css/p/ppcl3rr7n.css';
import '../../css/l/lxd_jw--n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s5d2dxbxx"/><rect class="ppcl3rr7n"/><path class="lxd_jw--n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:archive-outline" /></template>
