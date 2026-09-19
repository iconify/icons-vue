<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgrlo48fn.css';
import '../../css/b/b-r1xf_2r.css';
import '../../css/x/x9trttupz.css';
import '../../css/s/si-h3sona.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="fgrlo48fn"/><circle class="b-r1xf_2r"/><circle class="x9trttupz"/><path class="si-h3sona"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:code-working" /></template>
