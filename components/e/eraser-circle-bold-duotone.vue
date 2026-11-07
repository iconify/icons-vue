<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrdvcwidb.css';
import '../../css/v/vsmrr13db.css';
import '../../css/c/ch40nbb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdvcwidb"/><path class="vsmrr13db"/><path class="ch40nbb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eraser-circle-bold-duotone" /></template>
