<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6e5-ctfb.css';
import '../../css/i/i3rjp8brq.css';
import '../../css/o/o1g4_ci-r.css';
import '../../css/v/vzn707dmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6e5-ctfb"/><path class="i3rjp8brq"/><path clip-rule="evenodd" class="o1g4_ci-r"/><path class="vzn707dmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:garage-bold-duotone" /></template>
