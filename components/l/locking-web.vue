<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g2qll0bhn.css';
import '../../css/e/e9to63mfe.css';
import '../../css/n/n248iunwv.css';
import '../../css/l/ly-a8052m.css';
import '../../css/k/k1uq304yb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGe2lV0cbl"><g class="ft5dv1b6b"><path class="g2qll0bhn"/><path class="e9to63mfe"/><rect class="n248iunwv"/><path class="ly-a8052m"/><circle transform="matrix(0 -1 -1 0 10 14)" class="k1uq304yb"/><circle transform="matrix(0 -1 -1 0 16 14)" class="k1uq304yb"/></g></mask></defs><path mask="url(#SVGe2lV0cbl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:locking-web" /></template>
