<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="neup-dc5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-sync-corner-fill-sharp" /></template>
<style>
.neup-dc5n {
  fill: currentColor;
  d: path("M16 6v3a1 1 0 0 1-2 0v-.149c-2.712 1.537-7.288 1.537-10 0V11c0 .197.112.376.235.522c.26.307.613.527.97.705C6.34 12.794 7.743 13 9 13a1 1 0 0 1 0 2c-1.676 0-3.526-.313-5-1.149V16c0 .197.112.376.235.522c.26.307.613.527.97.705C6.34 17.794 7.743 18 9 18a1 1 0 0 1 0 2c-1.578 0-3.268-.274-4.69-.984c-.599-.3-1.166-.688-1.602-1.202C2.276 17.302 2 16.676 2 16V6c0-.676.276-1.302.708-1.814c2.465-2.913 10.119-2.913 12.584 0C15.724 4.698 16 5.324 16 6m2 8h.748a3.47 3.47 0 0 0-4.854 1.447a1 1 0 1 1-1.788-.894a5.4 5.4 0 0 1 1.025-1.422a5.4 5.4 0 0 1 1.422-1.025a5.46 5.46 0 0 1 5.447.317V12a1 1 0 0 1 2 0v3a1 1 0 0 1-.541.888h-.001A1 1 0 0 1 21 16h-3a1 1 0 0 1 0-2m-4 7.577V22a1 1 0 0 1-2 0v-3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894a5.4 5.4 0 0 1-1.025 1.422a5.4 5.4 0 0 1-1.422 1.025A5.46 5.46 0 0 1 14 21.577");
}

</style>
