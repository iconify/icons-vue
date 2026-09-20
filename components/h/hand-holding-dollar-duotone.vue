<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs7bwc8re.css';
import '../../css/w/wirx_bx0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs7bwc8re"/><path clip-rule="evenodd" class="wirx_bx0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:hand-holding-dollar-duotone" /></template>
