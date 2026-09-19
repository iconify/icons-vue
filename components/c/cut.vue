<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqc1mzcmu.css';
import '../../css/q/q2cblpihb.css';
import '../../css/b/brfj9ob1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cqc1mzcmu"/><path class="q2cblpihb"/><path class="brfj9ob1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:cut" /></template>
