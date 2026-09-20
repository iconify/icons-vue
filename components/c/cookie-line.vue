<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/burq9xbdf.css';
import '../../css/v/vjz9f7byi.css';
import '../../css/z/zt0bu9e2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="burq9xbdf"/><path class="vjz9f7byi"/><path class="zt0bu9e2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cookie-line" /></template>
