<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qosnnxx8l.css';
import '../../css/x/x41xvfi0c.css';
import '../../css/h/h0ezbvb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qosnnxx8l"/><path class="x41xvfi0c"/><path clip-rule="evenodd" class="h0ezbvb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:danger-triangle-outline" /></template>
