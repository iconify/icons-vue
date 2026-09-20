<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ty3tezb_y"/><path class="o62nstjip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-light-meteor" /></template>
<style>
.o62nstjip {
  fill: var(--svg-color--df4f4f, #df4f4f);
  d: path("m9.99 10.4l17.984 19.05a.84.84 0 0 0 1.081-.072a.8.8 0 0 0 .108-1.008zm5.694 1.805L29.38 26.97a.84.84 0 0 0 1.081-.072a.8.8 0 0 0 .108-1.008zm-4 3.853l13.7 14.764a.84.84 0 0 0 1.081-.072a.8.8 0 0 0 .108-1.008zm8.816-2.304l9.568 10.315a.586.586 0 0 0 .755-.05a.56.56 0 0 0 .076-.7l-10.4-9.56Zm-7.5 6.77l9.57 10.315a.586.586 0 0 0 .755-.05a.56.56 0 0 0 .076-.7zm12.415-4.538l4.337 4.689a.3.3 0 0 0 .374-.024a.25.25 0 0 0 .037-.33zM15.4 25.277l4.337 4.689a.3.3 0 0 0 .374-.024a.25.25 0 0 0 .037-.33z");
}

.ty3tezb_y {
  fill: var(--svg-color--bf5555, #bf5555);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

</style>
