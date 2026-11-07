<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg928d-qd.css';
import '../../css/v/vj271db3h.css';
import '../../css/b/b1eoogomv.css';
import '../../css/u/um80ms1wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path class="vj271db3h"/><path class="b1eoogomv"/><path class="um80ms1wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-archive-bold-duotone" /></template>
