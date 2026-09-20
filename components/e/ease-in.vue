<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agxbx8tpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agxbx8tpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ease-in" /></template>
