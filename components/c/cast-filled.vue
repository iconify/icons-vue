<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lud_oq9-e.css';
import '../../css/f/f3cbn2boa.css';
import '../../css/q/q8o975bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lud_oq9-e"/><path class="f3cbn2boa"/><path class="q8o975bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cast-filled" /></template>
