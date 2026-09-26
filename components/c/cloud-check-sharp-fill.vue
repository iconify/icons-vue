<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pc892x2wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-check-sharp-fill" /></template>
<style>
.pc892x2wy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 20L18 20C20.6233 20 23 17.6233 23 15C23 12.6937 21.163 10.578 18.9365 10.1004C18.4644 6.7612 15.4245 4 12 4C8.5755 4 5.5356 6.7612 5.0635 10.1004C2.837 10.578 1 12.6937 1 15C1 17.6233 3.3767 20 6 20ZM9.0885 13.2742L10.8608 15.0971C11.0491 15.2907 11.3077 15.4 11.5778 15.4C11.9262 15.4 12.2495 15.2187 12.4311 14.9214L15.0457 10.6429L13.3392 9.6L11.3965 12.779L10.5225 11.88L9.0885 13.2742Z");
}

</style>
