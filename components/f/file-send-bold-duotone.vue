<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgd8bzbml.css';
import '../../css/g/g5_-wqbhf.css';
import '../../css/s/sn15dubbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgd8bzbml"/><path class="g5_-wqbhf"/><path class="sn15dubbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-send-bold-duotone" /></template>
