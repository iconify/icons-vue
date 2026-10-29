<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc-koab6b.css';
import '../../css/m/m0g6xbd6f.css';
import '../../css/r/r7my--sgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc-koab6b"/><path class="m0g6xbd6f"/><path class="r7my--sgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:dumbbell" /></template>
