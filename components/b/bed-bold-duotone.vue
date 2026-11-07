<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv26kqbrj.css';
import '../../css/s/s7rjj21fg.css';
import '../../css/i/inygc8bcc.css';
import '../../css/a/auhv3ob1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv26kqbrj"/><path class="s7rjj21fg"/><path class="inygc8bcc"/><path class="auhv3ob1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bed-bold-duotone" /></template>
