<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwakcgbjk.css';
import '../../css/j/jhj59op0p.css';
import '../../css/q/qu56y6rrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wwakcgbjk"/><path class="jhj59op0p"/><path class="qu56y6rrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cryptpad" /></template>
