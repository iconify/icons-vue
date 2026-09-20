<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4-7eu8rv.css';
import '../../css/f/f84x_gb3e.css';
import '../../css/o/of7d1zb9r.css';
import '../../css/x/xq28ilqhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v4-7eu8rv"/><circle class="f84x_gb3e"/><circle class="of7d1zb9r"/><path class="xq28ilqhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:friendly" /></template>
