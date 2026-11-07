<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt-_h2mmy.css';
import '../../css/g/ge8axobmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nt-_h2mmy"/><path class="ge8axobmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-round-angle-bold-duotone" /></template>
