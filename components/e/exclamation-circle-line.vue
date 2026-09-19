<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngoo26b5w.css';
import '../../css/v/vr7sg0iag.css';
import '../../css/g/gyr35xsol.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 ngoo26b5w"/><path class="clr-i-outline clr-i-outline-path-2 vr7sg0iag"/><circle class="clr-i-outline clr-i-outline-path-3 gyr35xsol"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:exclamation-circle-line" /></template>
