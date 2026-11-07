<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p58c_4zdf.css';
import '../../css/s/sb7qghx4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p58c_4zdf"/><path class="sb7qghx4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-bold-duotone" /></template>
