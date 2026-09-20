<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xu52qhqlk"><path class="kmdh2on1u"/><path clip-rule="evenodd" class="axgyopbku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:keplr" /></template>
<style>
.axgyopbku {
  fill-rule: evenodd;
  d: path("M12 3c7.411 0 9 1.588 9 9c0 7.411-1.589 9-9 9s-9-1.589-9-9s1.588-9 9-9m5.882 3.11C15.702 3.93 11.3 4.8 8.05 8.05s-4.12 7.652-1.94 9.832s6.582 1.312 9.833-1.939c3.25-3.25 4.119-7.653 1.94-9.833");
}

.kmdh2on1u {
  d: path("M12.48 7.922c.13 1.336.196 2.004.546 2.494c.15.21.336.393.547.54c.495.343 1.164.4 2.502.512l.566.048v.968l-.566.048c-1.338.112-2.007.169-2.501.512c-.212.147-.397.33-.548.54c-.35.49-.415 1.158-.546 2.494h-.96c-.13-1.336-.196-2.004-.546-2.494a2.3 2.3 0 0 0-.547-.54c-.495-.343-1.164-.4-2.502-.512l-.566-.048v-.968l.566-.048c1.338-.112 2.007-.169 2.502-.512a2.3 2.3 0 0 0 .547-.54c.35-.49.415-1.158.546-2.494z");
}

.xu52qhqlk {
  fill: var(--svg-color--14afeb, #14afeb);
}

</style>
