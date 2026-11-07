<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czdsxrb2c.css';
import '../../css/f/fsmk2qbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czdsxrb2c"/><path class="fsmk2qbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-bolt-bold-duotone" /></template>
