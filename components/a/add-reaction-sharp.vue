<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9b_v1bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-reaction-sharp" /></template>
<style>
.t9b_v1bah {
  fill: currentColor;
  d: path("M20.5 6.5v-2h-2v-1h2v-2h1v2h2v1h-2v2zm-5.188 4.116q.467 0 .789-.327t.322-.793t-.326-.79q-.327-.321-.794-.321t-.789.326t-.322.793t.327.79q.326.322.793.322m-6.615 0q.466 0 .788-.327q.323-.327.323-.793q0-.467-.327-.79q-.327-.321-.793-.321q-.467 0-.789.326q-.322.327-.322.793q0 .467.326.79q.327.322.794.322m5.948 5.48q1.195-.79 1.801-2.096H7.554q.605 1.306 1.8 2.095t2.646.79t2.645-.79M12.003 21q-1.866 0-3.51-.708q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51q.709-1.643 1.924-2.859T8.49 3.709T12 3q.998 0 1.94.203q.943.203 1.79.603V6.5h2.75v2.77h2.109q.205.647.308 1.323Q21 11.266 21 12q0 1.868-.708 3.51t-1.924 2.858t-2.856 1.923t-3.509.709");
}

</style>
