<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbuw4i61g.css';
import '../../css/m/mk20stbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vbuw4i61g"/><path class="mk20stbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:eye-off-filled" /></template>
