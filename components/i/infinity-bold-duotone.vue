<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbcwdowdw.css';
import '../../css/c/crhlcxbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fbcwdowdw"/><path class="crhlcxbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:infinity-bold-duotone" /></template>
