<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0edu0xjc.css';
import '../../css/e/egv45zsgc.css';
import '../../css/g/gjagb39hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="g0edu0xjc"/><path class="egv45zsgc"/><path class="gjagb39hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:hot-tub" /></template>
