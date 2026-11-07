<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is_2cgerd.css';
import '../../css/s/s02o69bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="is_2cgerd"/><path class="s02o69bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-cancel-rounded-bold-duotone" /></template>
