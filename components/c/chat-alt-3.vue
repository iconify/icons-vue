<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi3l8-bkb.css';
import '../../css/r/rpkswgq3h.css';
import '../../css/d/dujhcdcuw.css';
import '../../css/r/rgq401bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi3l8-bkb"/><circle class="rpkswgq3h"/><circle class="dujhcdcuw"/><circle class="rgq401bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chat-alt-3" /></template>
