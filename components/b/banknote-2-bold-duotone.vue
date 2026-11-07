<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6dl3e4vb.css';
import '../../css/v/vcvfl_y1l.css';
import '../../css/m/msvwnyd-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6dl3e4vb"/><path clip-rule="evenodd" class="vcvfl_y1l"/><path class="msvwnyd-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:banknote-2-bold-duotone" /></template>
