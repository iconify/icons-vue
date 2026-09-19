<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbcy3hzsq.css';
import '../../css/l/lwa5up2ml.css';
import '../../css/r/rw27qob_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbcy3hzsq"/><path class="lwa5up2ml"/><path class="rw27qob_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:help-octagon" /></template>
