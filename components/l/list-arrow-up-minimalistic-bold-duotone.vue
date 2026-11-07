<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdarr4bmq.css';
import '../../css/h/hqrr-dbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bdarr4bmq"/><path class="hqrr-dbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-arrow-up-minimalistic-bold-duotone" /></template>
