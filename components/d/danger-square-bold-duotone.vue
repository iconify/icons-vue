<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2ynbdc9b.css';
import '../../css/i/iqdm2xbfi.css';
import '../../css/x/x41xvfi0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2ynbdc9b"/><path class="iqdm2xbfi"/><path class="x41xvfi0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:danger-square-bold-duotone" /></template>
